<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8b_w57wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z8b_w57wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cheese-remix" {...props}></Icon>
