<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj2rtrbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kj2rtrbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mini-expand-mirrored" {...props}></Icon>
