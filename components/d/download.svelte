<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnxj8rb3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="jnxj8rb3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:download" {...props}></Icon>
