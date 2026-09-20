<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0c16rc2r.css';
import '../../css/s/se4563bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0c16rc2r"/><path class="se4563bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:light-mode-hdr-bold" {...props}></Icon>
