<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur0oo-1qr.css';
import '../../css/q/quz16u80s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ur0oo-1qr"/><path class="quz16u80s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:backpack-48-bold" {...props}></Icon>
