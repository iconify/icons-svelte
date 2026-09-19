<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek6lbbb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ek6lbbb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrow-left" {...props}></Icon>
