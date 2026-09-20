<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qu7_qcjgl.css';
import '../../css/i/ip3qm20ze.css';
import '../../css/k/kr99ulpjv.css';
import '../../css/u/u66s-fbqm.css';
import '../../css/k/ko6o-6b9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qu7_qcjgl"/><path class="ip3qm20ze"/><path class="kr99ulpjv"/><path class="u66s-fbqm"/><path class="ko6o-6b9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quit-full-screen-circle-broken" {...props}></Icon>
