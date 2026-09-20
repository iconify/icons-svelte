<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tun-vsp7b.css';
import '../../css/l/lb_uwtm7d.css';
import '../../css/g/gfwzmm8cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tun-vsp7b"/><path class="lb_uwtm7d"/><path class="gfwzmm8cw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notebook-square-linear" {...props}></Icon>
