<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/envibddeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="envibddeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:medicine-bottle-fill" {...props}></Icon>
