<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1r2utbur.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b6ra2rkgs.css';
import '../../css/h/hyfvbjbmz.css';
import '../../css/x/xh7fozb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1r2utbur secondary"/><g class="dt0cm9dhy primary"><path class="b6ra2rkgs"/><path class="hyfvbjbmz"/><path class="xh7fozb3j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:burger-duo" {...props}></Icon>
