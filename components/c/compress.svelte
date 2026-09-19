<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9jz7db7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="i9jz7db7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:compress" {...props}></Icon>
