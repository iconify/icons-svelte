<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9l0rm1ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x9l0rm1ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:partition-specific" {...props}></Icon>
