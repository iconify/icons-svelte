<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8ildbc1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c8ildbc1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:github-action" {...props}></Icon>
