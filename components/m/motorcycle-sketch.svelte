<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hgykuurez.css';
import '../../css/w/w18n-2bbj.css';
import '../../css/e/eojrhrb4s.css';
import '../../css/m/manj_xg0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hgykuurez wm-k"/><path class="w18n-2bbj wm-a"/><path class="eojrhrb4s wm-k"/><path class="manj_xg0q wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:motorcycle-sketch" {...props}></Icon>
