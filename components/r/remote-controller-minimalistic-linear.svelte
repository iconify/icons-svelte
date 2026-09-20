<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bjcq8u-lh.css';
import '../../css/t/tyaij6rok.css';
import '../../css/v/vy5waob-q.css';
import '../../css/u/u3xw_g32v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bjcq8u-lh"/><path class="tyaij6rok"/><path class="vy5waob-q"/><path class="u3xw_g32v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:remote-controller-minimalistic-linear" {...props}></Icon>
