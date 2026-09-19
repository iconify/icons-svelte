<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nluxe8cbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nluxe8cbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:arrow-thick-from-left" {...props}></Icon>
