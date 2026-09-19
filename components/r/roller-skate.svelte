<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cslcpehvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cslcpehvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:roller-skate" {...props}></Icon>
