<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdcurrben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cdcurrben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chevron-circle-right" {...props}></Icon>
