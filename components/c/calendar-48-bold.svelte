<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwjkdv1oe.css';
import '../../css/g/gslqnkb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vwjkdv1oe"/><path class="gslqnkb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-48-bold" {...props}></Icon>
