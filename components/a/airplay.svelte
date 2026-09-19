<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggisaj66z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":408};
const content = `<path class="ggisaj66z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:airplay" {...props}></Icon>
