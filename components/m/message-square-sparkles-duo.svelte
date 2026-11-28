<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akzm_vtle.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t0f2x9b0h.css';
import '../../css/a/af_7eacyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akzm_vtle secondary"/><g class="dt0cm9dhy primary"><path class="t0f2x9b0h"/><path class="af_7eacyu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-sparkles-duo" {...props}></Icon>
