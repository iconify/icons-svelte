<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rig2rlqlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rig2rlqlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:copy" {...props}></Icon>
