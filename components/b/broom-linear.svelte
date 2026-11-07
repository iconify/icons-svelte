<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wi1qbk5_i.css';
import '../../css/k/kt6370brf.css';
import '../../css/b/bvwkol5hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wi1qbk5_i"/><path class="kt6370brf"/><path class="bvwkol5hk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:broom-linear" {...props}></Icon>
