<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khunfubsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khunfubsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:book-sparkle-fill-round" {...props}></Icon>
