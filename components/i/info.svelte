<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km3o8g18s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":512};
const content = `<path class="km3o8g18s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:info" {...props}></Icon>
