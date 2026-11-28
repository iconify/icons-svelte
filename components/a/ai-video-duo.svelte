<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-cwpshed.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bouczrbwq.css';
import '../../css/q/qgoj2cb0j.css';
import '../../css/h/hd8ymvble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-cwpshed secondary"/><g class="dt0cm9dhy primary"><path class="bouczrbwq"/><path class="qgoj2cb0j"/><path class="hd8ymvble"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-video-duo" {...props}></Icon>
