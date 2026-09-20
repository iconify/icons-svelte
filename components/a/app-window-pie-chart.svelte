<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/s/s3_lo5eyl.css';
import '../../css/o/ok-uoxbmh.css';
import '../../css/q/qonxbbjwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s3_lo5eyl"/><path class="ok-uoxbmh"/><path class="qonxbbjwm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:app-window-pie-chart" {...props}></Icon>
