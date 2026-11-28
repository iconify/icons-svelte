<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea5taoauh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ekf8t7boi.css';
import '../../css/q/qbsr-mb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea5taoauh secondary"/><g class="dt0cm9dhy primary"><path class="ekf8t7boi"/><path class="qbsr-mb7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heart-pulse-duo" {...props}></Icon>
