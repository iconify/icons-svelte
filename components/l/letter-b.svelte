<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0u3abb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0u3abb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:letter-b" {...props}></Icon>
