<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/if_fr7tub.css';
import '../../css/p/pb0h07b3i.css';
import '../../css/o/o_e4ed8vb.css';
import '../../css/b/b-ozjw1lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="if_fr7tub"/><path class="pb0h07b3i"/><path class="o_e4ed8vb"/><path class="b-ozjw1lj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bar-chart-horizontal-duo" {...props}></Icon>
