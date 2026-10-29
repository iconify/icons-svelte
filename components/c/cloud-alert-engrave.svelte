<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nezjtixvo.css';
import '../../css/f/ftut6hr7j.css';
import '../../css/c/cvilh7buk.css';
import '../../css/g/g56b45b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nezjtixvo wm-k"/><path class="ftut6hr7j wm-shadow"/><path class="cvilh7buk wm-k"/><path class="g56b45b0x wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-alert-engrave" {...props}></Icon>
