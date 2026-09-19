<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvflfbb-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dvflfbb-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pentagon-left-outline" {...props}></Icon>
