<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oib00zb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oib00zb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:pied-piper-hat" {...props}></Icon>
