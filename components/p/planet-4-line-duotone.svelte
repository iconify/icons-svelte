<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cclx108-u.css';
import '../../css/i/im_dd0b1k.css';
import '../../css/x/x0fuh28ql.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/k/ks3_y11ze.css';
import '../../css/z/zmowo9bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cclx108-u"/><path class="im_dd0b1k"/><path class="x0fuh28ql"/><g class="mc2zb0bvp"><path class="ks3_y11ze"/><path class="zmowo9bil"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:planet-4-line-duotone" {...props}></Icon>
