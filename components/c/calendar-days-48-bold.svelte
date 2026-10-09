<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwjkdv1oe.css';
import '../../css/h/h0rijs3in.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vwjkdv1oe"/><path class="h0rijs3in"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-days-48-bold" {...props}></Icon>
