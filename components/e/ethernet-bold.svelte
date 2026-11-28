<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfjt46bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mfjt46bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:ethernet-bold" {...props}></Icon>
