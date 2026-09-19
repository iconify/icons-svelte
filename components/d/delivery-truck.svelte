<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf7wg8b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bf7wg8b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:delivery-truck" {...props}></Icon>
