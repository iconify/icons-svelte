<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqo5rw4pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tqo5rw4pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:alarm-clock-cancelled" {...props}></Icon>
