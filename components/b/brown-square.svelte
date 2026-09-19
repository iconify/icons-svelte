<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmjl3i6pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rmjl3i6pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:brown-square" {...props}></Icon>
