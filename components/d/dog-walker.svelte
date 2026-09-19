<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b63ho8b4l.css';
import '../../css/v/vqcm1iv2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b63ho8b4l"/><path class="vqcm1iv2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:dog-walker" {...props}></Icon>
