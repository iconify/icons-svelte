<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-479s9ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-479s9ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-underline-wavy" {...props}></Icon>
