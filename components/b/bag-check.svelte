<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpxo15b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xpxo15b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bag-check" {...props}></Icon>
