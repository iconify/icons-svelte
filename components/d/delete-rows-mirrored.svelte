<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl5m2ibfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jl5m2ibfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:delete-rows-mirrored" {...props}></Icon>
