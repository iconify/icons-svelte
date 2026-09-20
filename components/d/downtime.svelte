<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpj0icx7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lpj0icx7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:downtime" {...props}></Icon>
