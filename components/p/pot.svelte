<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs_zt8b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vs_zt8b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:pot" {...props}></Icon>
