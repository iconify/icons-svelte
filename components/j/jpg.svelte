<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw32gyb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yw32gyb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:jpg" {...props}></Icon>
