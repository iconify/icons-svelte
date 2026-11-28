<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/if_fr7tub.css';
import '../../css/v/vorae3l_s.css';
import '../../css/j/jbhde45qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="if_fr7tub"/><path class="vorae3l_s"/><path class="jbhde45qr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-column-big" {...props}></Icon>
