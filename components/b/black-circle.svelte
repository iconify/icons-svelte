<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl81vn0ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jl81vn0ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:black-circle" {...props}></Icon>
