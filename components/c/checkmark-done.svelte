<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdt5yo5_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vdt5yo5_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:checkmark-done" {...props}></Icon>
