<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wqxwhwbjw.css';
import '../../css/t/tvs-qo4vm.css';
import '../../css/o/oh_l5zboi.css';
import '../../css/r/r8y-lxhat.css';
import '../../css/f/f0_omibpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wqxwhwbjw"/><path class="tvs-qo4vm wm-shadow"/><path class="oh_l5zboi"/><path class="r8y-lxhat"/><path class="f0_omibpb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:nutcracker-engrave" {...props}></Icon>
