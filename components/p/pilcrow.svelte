<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-zn_rb4f.css';
import '../../css/v/vp_-scb_a.css';
import '../../css/i/ios73fbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k z-zn_rb4f"/><path class="vp_-scb_a wm-k"/><path class="ios73fbpx wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:pilcrow" {...props}></Icon>
