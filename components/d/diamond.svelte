<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-uhadh3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i-uhadh3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:diamond" {...props}></Icon>
