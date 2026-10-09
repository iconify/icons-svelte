<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwjkdv1oe.css';
import '../../css/c/ccoa7kjog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vwjkdv1oe"/><path class="ccoa7kjog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-range-48-bold" {...props}></Icon>
