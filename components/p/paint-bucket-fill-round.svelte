<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klugf78fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klugf78fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paint-bucket-fill-round" {...props}></Icon>
