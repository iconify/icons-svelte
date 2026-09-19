<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8g3i3bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="r8g3i3bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:dock-right" {...props}></Icon>
