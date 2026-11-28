<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq2le3bll.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/h/hwr7riwkr.css';
import '../../css/l/l87c0nb7d.css';
import '../../css/r/r851mssgl.css';
import '../../css/l/lcx6pvbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary wq2le3bll"/><g class="dt0cm9dhy primary"><path class="hwr7riwkr"/><path class="l87c0nb7d"/><path class="r851mssgl"/><path class="lcx6pvbtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grab-duo" {...props}></Icon>
