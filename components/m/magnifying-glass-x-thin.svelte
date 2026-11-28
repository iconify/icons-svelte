<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnwy0xbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bnwy0xbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:magnifying-glass-x-thin" {...props}></Icon>
