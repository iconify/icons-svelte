<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwjkdv1oe.css';
import '../../css/b/b3suifbrv.css';
import '../../css/k/k_owl0bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vwjkdv1oe"/><path class="b3suifbrv"/><path class="k_owl0bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calendar-plus-48-bold" {...props}></Icon>
