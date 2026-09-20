<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kumxoab-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kumxoab-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:calendar-2" {...props}></Icon>
