<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l33qbtbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="l33qbtbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:box-gift-1" {...props}></Icon>
