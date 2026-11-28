<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u90bv9bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u90bv9bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:license-plate" {...props}></Icon>
