<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv0lhnksd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jv0lhnksd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pressure-filled" {...props}></Icon>
