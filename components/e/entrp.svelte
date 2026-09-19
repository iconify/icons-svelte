<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1cb0d2jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b1cb0d2jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:entrp" {...props}></Icon>
