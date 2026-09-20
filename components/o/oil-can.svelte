<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvm3nfb0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vvm3nfb0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:oil-can" {...props}></Icon>
