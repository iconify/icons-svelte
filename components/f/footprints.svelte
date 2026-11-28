<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/ku0xfq--d.css';
import '../../css/u/ubfqcobgc.css';
import '../../css/v/vp3srkb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ku0xfq--d"/><path class="ubfqcobgc"/><path class="vp3srkb8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:footprints" {...props}></Icon>
