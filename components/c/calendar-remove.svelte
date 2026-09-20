<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccyoe_b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="ccyoe_b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:calendar-remove" {...props}></Icon>
