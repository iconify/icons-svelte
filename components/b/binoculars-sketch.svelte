<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hbz15abgu.css';
import '../../css/h/hobwr1b0j.css';
import '../../css/h/h0cjjvbnh.css';
import '../../css/h/hfny-hbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hbz15abgu"/><path class="hobwr1b0j wm-a"/><path class="h0cjjvbnh wm-k"/><path class="hfny-hbfu wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:binoculars-sketch" {...props}></Icon>
