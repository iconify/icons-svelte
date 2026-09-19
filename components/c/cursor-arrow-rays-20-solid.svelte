<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c003x8brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c003x8brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cursor-arrow-rays-20-solid" {...props}></Icon>
