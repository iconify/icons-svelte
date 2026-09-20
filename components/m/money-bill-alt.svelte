<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px5xjv6ok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="px5xjv6ok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:money-bill-alt" {...props}></Icon>
