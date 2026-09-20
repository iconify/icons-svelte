<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nivuwwbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nivuwwbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-variant-closed" {...props}></Icon>
