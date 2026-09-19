<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/s/stzadlb3s.css';
import '../../css/p/prngzwbds.css';
import '../../css/y/yzeqrjb-a.css';
import '../../css/o/o8x_1pkko.css';
import '../../css/r/rygkaxbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="stzadlb3s"/><path class="prngzwbds"/><circle class="yzeqrjb-a"/><path class="o8x_1pkko"/><path class="rygkaxbgg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:rocket-outline" {...props}></Icon>
