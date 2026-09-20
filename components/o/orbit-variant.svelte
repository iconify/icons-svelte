<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv_pdp-8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv_pdp-8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:orbit-variant" {...props}></Icon>
