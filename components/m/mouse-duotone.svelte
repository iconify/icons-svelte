<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mwidq8eyg.css';
import '../../css/w/wcn5vdzhi.css';
import '../../css/p/ps0g5sbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mwidq8eyg"/><path class="wcn5vdzhi"/><path class="ps0g5sbmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:mouse-duotone" {...props}></Icon>
