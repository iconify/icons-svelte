<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og45dbcwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="og45dbcwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:draw" {...props}></Icon>
