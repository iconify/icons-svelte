<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiyaqjb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fiyaqjb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hamburger-open" {...props}></Icon>
