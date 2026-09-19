<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk5v4w-nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sk5v4w-nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-075" {...props}></Icon>
