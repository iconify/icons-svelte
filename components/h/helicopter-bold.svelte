<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufpt_wb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ufpt_wb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:helicopter-bold" {...props}></Icon>
