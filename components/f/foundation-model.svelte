<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsm8ocbmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rsm8ocbmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:foundation-model" {...props}></Icon>
