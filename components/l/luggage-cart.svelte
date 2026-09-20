<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt-eubb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jt-eubb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:luggage-cart" {...props}></Icon>
