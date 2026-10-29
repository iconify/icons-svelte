<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/utejzabus.css';
import '../../css/q/q8dj_4b9d.css';
import '../../css/i/i9kv_6bto.css';
import '../../css/d/dowp58bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="utejzabus"/><path class="q8dj_4b9d wm-k"/><path class="i9kv_6bto wm-k"/><path class="dowp58bga wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:paste-sketch" {...props}></Icon>
