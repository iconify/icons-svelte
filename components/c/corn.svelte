<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/n/nmjmamnbd.css';
import '../../css/g/gbbwmvbvf.css';
import '../../css/r/reqp0xphh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="nmjmamnbd"/><path class="gbbwmvbvf"/><path class="reqp0xphh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corn" {...props}></Icon>
