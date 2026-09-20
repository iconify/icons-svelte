<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9ka4w-1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9ka4w-1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:finder-line" {...props}></Icon>
