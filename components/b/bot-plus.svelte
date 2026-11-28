<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0a8wrhwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0a8wrhwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bot-plus" {...props}></Icon>
