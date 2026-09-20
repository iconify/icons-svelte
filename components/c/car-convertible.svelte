<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyy95cbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyy95cbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-convertible" {...props}></Icon>
