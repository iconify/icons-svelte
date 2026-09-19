<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iho8i0bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="iho8i0bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:increase-indent-arrow-mirrored" {...props}></Icon>
