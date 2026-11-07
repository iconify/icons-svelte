<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f3p-g4m6q.css';
import '../../css/s/smcsc6bgv.css';
import '../../css/i/iyts3fg-w.css';
import '../../css/u/untnup1qs.css';
import '../../css/h/hpzuy57gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f3p-g4m6q"/><path class="smcsc6bgv"/><path class="iyts3fg-w"/><path class="untnup1qs"/><path class="hpzuy57gm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:jar-of-pills-linear" {...props}></Icon>
