<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v0wvqj6_x.css';
import '../../css/h/h_tsn8bxt.css';
import '../../css/s/s4v36abdu.css';
import '../../css/w/wr4dgn3dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v0wvqj6_x"/><circle class="h_tsn8bxt"/><path class="s4v36abdu"/><path class="wr4dgn3dm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:internet-antenna-01" {...props}></Icon>
