<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qdycs8m8j.css';
import '../../css/o/o409egb8b.css';
import '../../css/o/oqf382uiz.css';
import '../../css/h/hbi8hhkfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qdycs8m8j wm-k"/><path class="o409egb8b wm-shadow"/><path class="oqf382uiz wm-k"/><path class="hbi8hhkfx wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:eye-engrave" {...props}></Icon>
