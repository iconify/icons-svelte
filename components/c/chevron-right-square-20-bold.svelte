<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fec4cjbkq.css';
import '../../css/a/atj8-5bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fec4cjbkq"/><path class="atj8-5bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-right-square-20-bold" {...props}></Icon>
