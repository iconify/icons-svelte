<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4ur0fbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4ur0fbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:airplane-seat" {...props}></Icon>
