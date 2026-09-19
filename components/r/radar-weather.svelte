<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_m7qkb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y_m7qkb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:radar-weather" {...props}></Icon>
