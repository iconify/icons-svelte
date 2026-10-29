<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cur66cgez.css';
import '../../css/j/jlz57qpcn.css';
import '../../css/s/spe3eibot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cur66cgez wm-a"/><path class="jlz57qpcn wm-k"/><path class="spe3eibot wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chart-bar-increasing-sketch" {...props}></Icon>
