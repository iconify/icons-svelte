<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f_d6gcbvr.css';
import '../../css/e/e82k79bum.css';
import '../../css/o/oix2qy57j.css';
import '../../css/e/eu5ukbiiu.css';
import '../../css/w/wotccxbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f_d6gcbvr wm-k"/><path class="e82k79bum wm-a"/><path class="oix2qy57j wm-shadow"/><path class="eu5ukbiiu wm-a"/><path class="wm-k wotccxbib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-open-engrave" {...props}></Icon>
