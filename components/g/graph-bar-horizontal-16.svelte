<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czzl2nbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="czzl2nbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:graph-bar-horizontal-16" {...props}></Icon>
