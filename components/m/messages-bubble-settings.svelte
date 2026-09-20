<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc6xhac8s.css';
import '../../css/b/bfv7rkbai.css';
import '../../css/d/ds-s0gbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc6xhac8s"/><path class="bfv7rkbai"/><path class="ds-s0gbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:messages-bubble-settings" {...props}></Icon>
