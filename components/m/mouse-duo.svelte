<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj494dplb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/frwj1bkcb.css';
import '../../css/l/lfjpy4bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj494dplb secondary"/><g class="dt0cm9dhy primary"><path class="frwj1bkcb"/><path class="lfjpy4bqg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mouse-duo" {...props}></Icon>
