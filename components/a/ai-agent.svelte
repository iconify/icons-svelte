<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/t4d7rpbqj.css';
import '../../css/e/e9v8jcb4j.css';
import '../../css/g/g16brbwge.css';
import '../../css/s/snlvk-mhf.css';
import '../../css/j/jhniv1ffu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="t4d7rpbqj"/><path class="e9v8jcb4j"/><path class="g16brbwge"/><path class="snlvk-mhf"/><path class="jhniv1ffu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-agent" {...props}></Icon>
