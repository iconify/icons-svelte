<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xczynybrx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/ju4crf5-e.css';
import '../../css/z/zxr8z_oqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary xczynybrx"/><g class="dt0cm9dhy primary"><path class="ju4crf5-e"/><path class="zxr8z_oqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hdmi-port-duo" {...props}></Icon>
