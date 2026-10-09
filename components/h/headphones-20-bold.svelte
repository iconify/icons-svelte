<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_w8mhbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i_w8mhbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:headphones-20-bold" {...props}></Icon>
