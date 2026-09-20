<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otjmwacby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otjmwacby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:badge-4k-sharp" {...props}></Icon>
