<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo9o1ccjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eo9o1ccjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:reset-alt" {...props}></Icon>
