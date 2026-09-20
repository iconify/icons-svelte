<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnagvx03c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnagvx03c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bus-wrench" {...props}></Icon>
