<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhm5lux_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yhm5lux_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:receipt-subtract-remix" {...props}></Icon>
