<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql5xq868z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ql5xq868z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:calendar-clear-sharp" {...props}></Icon>
