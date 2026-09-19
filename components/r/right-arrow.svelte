<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz29c9t9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uz29c9t9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:right-arrow" {...props}></Icon>
