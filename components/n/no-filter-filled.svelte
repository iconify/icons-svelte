<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jat1igb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jat1igb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:no-filter-filled" {...props}></Icon>
