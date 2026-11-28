<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tij9s_4ga.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sxtt7ca6r.css';
import '../../css/m/mydyanbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary tij9s_4ga"/><g class="dt0cm9dhy primary"><path class="sxtt7ca6r"/><path class="mydyanbos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:egg-fried-duo" {...props}></Icon>
