<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpy23lbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bpy23lbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:mail-icon-1" {...props}></Icon>
