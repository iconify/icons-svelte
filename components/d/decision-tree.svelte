<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8_76bc0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h8_76bc0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:decision-tree" {...props}></Icon>
