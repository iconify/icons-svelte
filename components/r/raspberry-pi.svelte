<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc0eu1bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fc0eu1bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:raspberry-pi" {...props}></Icon>
