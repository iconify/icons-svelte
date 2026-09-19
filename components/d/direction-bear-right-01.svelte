<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp1h99b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cp1h99b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-bear-right-01" {...props}></Icon>
