<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omryxacrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="omryxacrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:apparel" {...props}></Icon>
