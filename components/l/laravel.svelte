<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi3emcc5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi3emcc5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:laravel" {...props}></Icon>
