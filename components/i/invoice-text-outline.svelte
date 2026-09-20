<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr1o9hbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr1o9hbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-outline" {...props}></Icon>
