<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/f48nptbwr.css';
import '../../css/q/q28vbyb0k.css';
import '../../css/y/yek47efby.css';
import '../../css/r/rd2xrl-rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="f48nptbwr"/><path class="q28vbyb0k"/><path class="yek47efby"/><path class="rd2xrl-rf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ice-cream" {...props}></Icon>
