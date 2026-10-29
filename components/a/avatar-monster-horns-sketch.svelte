<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wejio6ivs.css';
import '../../css/h/hq38tccqi.css';
import '../../css/y/yjuie1_qo.css';
import '../../css/k/k_1g644cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wejio6ivs"/><path class="hq38tccqi wm-a"/><path class="wm-k yjuie1_qo"/><path class="k_1g644cr wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-monster-horns-sketch" {...props}></Icon>
