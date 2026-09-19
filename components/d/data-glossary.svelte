<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awlo-z2_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="awlo-z2_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-glossary" {...props}></Icon>
