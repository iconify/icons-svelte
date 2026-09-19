<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llp-4sbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="llp-4sbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:image-crosshair" {...props}></Icon>
