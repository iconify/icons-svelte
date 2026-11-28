<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5160pbdf.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f5ro_pbbz.css';
import '../../css/h/h6mtbcfpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5160pbdf secondary"/><g class="dt0cm9dhy primary"><path class="f5ro_pbbz"/><path class="h6mtbcfpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pin-duo" {...props}></Icon>
