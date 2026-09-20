<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnfbogben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vnfbogben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:hamburger-sidebar" {...props}></Icon>
