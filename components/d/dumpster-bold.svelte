<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txd9fd4nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="txd9fd4nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:dumpster-bold" {...props}></Icon>
