<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt1bfvb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vt1bfvb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:caret-solid-down" {...props}></Icon>
