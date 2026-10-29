<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lztux4j4y.css';
import '../../css/g/ghyktpbhu.css';
import '../../css/c/c91kb2byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lztux4j4y"/><path class="ghyktpbhu wm-a"/><path class="c91kb2byc wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:alarm-clock-check" {...props}></Icon>
