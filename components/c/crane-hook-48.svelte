<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo1gldv5s.css';
import '../../css/f/fjkjw2x4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uo1gldv5s"/><path class="fjkjw2x4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crane-hook-48" {...props}></Icon>
