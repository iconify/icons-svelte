<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fs4bv7bod.css';
import '../../css/p/psnkz2bcb.css';
import '../../css/a/a28-wzbev.css';
import '../../css/v/v0rdnccee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fs4bv7bod wm-shadow"/><path class="psnkz2bcb wm-k"/><circle class="a28-wzbev wm-a"/><path class="v0rdnccee wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:camera-off-engrave" {...props}></Icon>
