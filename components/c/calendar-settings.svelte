<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma32ezb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ma32ezb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:calendar-settings" {...props}></Icon>
