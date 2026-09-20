<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n09x0rbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n09x0rbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-minus-multiple-outline" {...props}></Icon>
