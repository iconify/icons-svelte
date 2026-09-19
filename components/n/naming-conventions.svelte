<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su4tvivsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="su4tvivsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:naming-conventions" {...props}></Icon>
