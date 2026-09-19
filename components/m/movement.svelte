<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb9sa7noz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bb9sa7noz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:movement" {...props}></Icon>
