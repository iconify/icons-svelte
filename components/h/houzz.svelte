<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it41hmb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="it41hmb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:houzz" {...props}></Icon>
