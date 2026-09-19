<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-i_uiwdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-i_uiwdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:cotton-bureau" {...props}></Icon>
