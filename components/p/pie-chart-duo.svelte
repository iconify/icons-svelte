<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxo1awbgx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/ud95brdct.css';
import '../../css/u/umys868ag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxo1awbgx secondary"/><g class="dt0cm9dhy primary"><path class="ud95brdct"/><path class="umys868ag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pie-chart-duo" {...props}></Icon>
