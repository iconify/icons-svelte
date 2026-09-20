<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7z33-zvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f7z33-zvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pickup-truck-with-slidein-camper" {...props}></Icon>
