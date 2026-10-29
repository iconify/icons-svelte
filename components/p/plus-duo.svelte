<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4tx7yf5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4tx7yf5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:plus-duo" {...props}></Icon>
