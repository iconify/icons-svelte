<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p37_k_s9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p37_k_s9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:digital-identity" {...props}></Icon>
