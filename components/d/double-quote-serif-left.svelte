<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zizo1ybwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zizo1ybwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:double-quote-serif-left" {...props}></Icon>
