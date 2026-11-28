<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/m/mjyz-pbuf.css';
import '../../css/j/j1qxisssa.css';
import '../../css/j/jzv2cpbts.css';
import '../../css/v/ve59fqbly.css';
import '../../css/y/yto511bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="mjyz-pbuf"/><path class="j1qxisssa"/><path class="jzv2cpbts"/><path class="ve59fqbly"/><path class="yto511bre"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hand-sparkles" {...props}></Icon>
