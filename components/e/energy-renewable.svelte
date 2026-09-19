<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j39ox-dfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j39ox-dfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:energy-renewable" {...props}></Icon>
