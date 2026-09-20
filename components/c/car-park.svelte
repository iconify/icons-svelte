<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p03tihhfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p03tihhfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-park" {...props}></Icon>
