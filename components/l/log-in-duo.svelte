<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ahhc2jbks.css';
import '../../css/r/rw0tps2ji.css';
import '../../css/f/fs4i84bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ahhc2jbks"/><path class="rw0tps2ji"/><path class="fs4i84bmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:log-in-duo" {...props}></Icon>
