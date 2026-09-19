<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5nekx9ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t5nekx9ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:add-parent-node" {...props}></Icon>
