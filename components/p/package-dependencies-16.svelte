<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/both_jbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="both_jbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:package-dependencies-16" {...props}></Icon>
