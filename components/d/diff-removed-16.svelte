<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whcnm8bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="whcnm8bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-removed-16" {...props}></Icon>
