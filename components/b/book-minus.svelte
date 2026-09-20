<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpng_obri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpng_obri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-minus" {...props}></Icon>
