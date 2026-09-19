<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdun30biy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wdun30biy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:finger-print-outline" {...props}></Icon>
