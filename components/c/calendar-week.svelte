<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxvt__b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="lxvt__b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:calendar-week" {...props}></Icon>
