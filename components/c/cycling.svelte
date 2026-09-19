<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuhs32-ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="tuhs32-ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:cycling" {...props}></Icon>
