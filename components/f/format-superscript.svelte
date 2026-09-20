<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvosu6bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvosu6bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-superscript" {...props}></Icon>
