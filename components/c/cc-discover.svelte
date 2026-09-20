<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r99c2sbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r99c2sbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cc-discover" {...props}></Icon>
