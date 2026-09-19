<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owsatlbcf.css';
import '../../css/r/riavwwb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="owsatlbcf"/><path class="riavwwb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ai-recommend" {...props}></Icon>
