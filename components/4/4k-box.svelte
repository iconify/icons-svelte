<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct0n9sbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ct0n9sbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:4k-box" {...props}></Icon>
