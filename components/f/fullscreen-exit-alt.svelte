<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do-zxyb4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="do-zxyb4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:fullscreen-exit-alt" {...props}></Icon>
