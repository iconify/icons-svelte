<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep1is8b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ep1is8b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-unreal" {...props}></Icon>
