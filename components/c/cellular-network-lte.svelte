<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy4xbiqqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wy4xbiqqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:cellular-network-lte" {...props}></Icon>
