<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq9r4qbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mq9r4qbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ebay" {...props}></Icon>
