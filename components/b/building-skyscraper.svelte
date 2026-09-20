<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl5644buh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl5644buh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:building-skyscraper" {...props}></Icon>
