<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuh5o5c9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iuh5o5c9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-column" {...props}></Icon>
