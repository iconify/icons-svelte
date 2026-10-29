<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mj3898byv.css';
import '../../css/v/vlrbihbra.css';
import '../../css/p/piis-qmmh.css';
import '../../css/m/mrpsvib8v.css';
import '../../css/e/e4v6jpbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mj3898byv wm-k"/><path class="vlrbihbra wm-a"/><path class="piis-qmmh wm-shadow"/><path class="mrpsvib8v wm-k"/><path class="e4v6jpbkb wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rotate-ccw-engrave" {...props}></Icon>
