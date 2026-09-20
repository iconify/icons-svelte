<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgxb__bke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wgxb__bke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:four-legged-squid" {...props}></Icon>
