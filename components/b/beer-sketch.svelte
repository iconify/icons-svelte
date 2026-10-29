<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wfwb433hg.css';
import '../../css/y/yrv74sbtp.css';
import '../../css/j/jsqpoxyat.css';
import '../../css/t/tzhu-rhme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wfwb433hg wm-k"/><path class="wm-a yrv74sbtp"/><path class="jsqpoxyat wm-k"/><path class="tzhu-rhme wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:beer-sketch" {...props}></Icon>
