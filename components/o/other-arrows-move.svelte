<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_0enm4cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r_0enm4cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-arrows-move" {...props}></Icon>
