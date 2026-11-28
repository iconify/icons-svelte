<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psxbs1bui.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/y/ymh9xht4i.css';
import '../../css/s/s2luam95m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psxbs1bui secondary"/><g class="dt0cm9dhy primary"><path class="l4--ovbba"/><path class="ymh9xht4i"/><path class="s2luam95m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-korean-won-duo" {...props}></Icon>
