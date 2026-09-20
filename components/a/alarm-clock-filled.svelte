<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3ochbcej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y3ochbcej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:alarm-clock-filled" {...props}></Icon>
