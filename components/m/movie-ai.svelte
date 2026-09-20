<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf5gxbc2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf5gxbc2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:movie-ai" {...props}></Icon>
