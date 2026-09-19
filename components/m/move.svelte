<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa_28r6oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sa_28r6oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:move" {...props}></Icon>
