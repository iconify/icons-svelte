<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe-ilcc4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pe-ilcc4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:right-panel-close" {...props}></Icon>
