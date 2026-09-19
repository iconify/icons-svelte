<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dor8m7bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dor8m7bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:e-discovery" {...props}></Icon>
