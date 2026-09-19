<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ariq7rbyx.css';
import '../../css/r/r8qtg0eea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ariq7rbyx"/><path class="r8qtg0eea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:customer" {...props}></Icon>
