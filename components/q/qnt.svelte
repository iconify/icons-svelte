<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln0oy5k6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ln0oy5k6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:qnt" {...props}></Icon>
