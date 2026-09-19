<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7eoc6b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x7eoc6b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:microscope" {...props}></Icon>
