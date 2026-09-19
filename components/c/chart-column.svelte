<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8-5lw43z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n8-5lw43z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chart-column" {...props}></Icon>
