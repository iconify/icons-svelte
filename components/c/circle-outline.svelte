<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0_1vs7im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w0_1vs7im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:circle-outline" {...props}></Icon>
