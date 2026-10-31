<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0bv-nbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0bv-nbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-pin-close-fill-round" {...props}></Icon>
