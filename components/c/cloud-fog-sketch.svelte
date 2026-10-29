<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/ux9cud9mt.css';
import '../../css/h/hfc2uy8bf.css';
import '../../css/r/ru6p1kbvy.css';
import '../../css/n/nerchcc2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ux9cud9mt"/><path class="hfc2uy8bf wm-a"/><path class="ru6p1kbvy wm-k"/><path class="nerchcc2i wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-fog-sketch" {...props}></Icon>
