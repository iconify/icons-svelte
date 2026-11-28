<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2rly0bxh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rx0sv3t6f.css';
import '../../css/v/v--amgbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary w2rly0bxh"/><g class="dt0cm9dhy primary"><path class="rx0sv3t6f"/><path class="v--amgbvl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:donut-duo" {...props}></Icon>
