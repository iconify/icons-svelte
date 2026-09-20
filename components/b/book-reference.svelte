<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf5gvfb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tf5gvfb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:book-reference" {...props}></Icon>
