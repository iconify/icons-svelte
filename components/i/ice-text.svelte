<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iihsfd9nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="iihsfd9nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ice-text" {...props}></Icon>
