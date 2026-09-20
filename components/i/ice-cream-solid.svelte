<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q727zvbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q727zvbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ice-cream-solid" {...props}></Icon>
