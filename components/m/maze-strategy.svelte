<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/m/mve0jibyn.css';
import '../../css/d/dly0bybrd.css';
import '../../css/x/xjjvqp5zj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mve0jibyn"/><path class="dly0bybrd"/><path class="xjjvqp5zj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:maze-strategy" {...props}></Icon>
