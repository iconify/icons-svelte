<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8jfpbcsr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/e5zqveb5m.css';
import '../../css/w/w7_mhrwuu.css';
import '../../css/k/k8gzt_h4u.css';
import '../../css/b/bhu664byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8jfpbcsr secondary"/><g class="dt0cm9dhy primary"><path class="e5zqveb5m"/><path class="w7_mhrwuu"/><path class="k8gzt_h4u"/><path class="bhu664byo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:calendar-clock-duo" {...props}></Icon>
