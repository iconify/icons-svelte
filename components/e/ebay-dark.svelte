<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tabtax0oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tabtax0oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ebay-dark" {...props}></Icon>
