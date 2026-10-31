<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t4loxubrc.css';
import '../../css/w/w67figubd.css';
import '../../css/g/gti5w8btx.css';
import '../../css/c/cung03bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t4loxubrc wm-k"/><path class="w67figubd wm-deco"/><path class="gti5w8btx wm-k"/><path class="cung03bja wm-shadow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-valentine:rolling-pin" {...props}></Icon>
