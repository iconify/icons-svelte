<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfppa6zwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gfppa6zwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-setting-wrench-crescent-tool-construction-tools-wrench-setting-edit-adjust" {...props}></Icon>
