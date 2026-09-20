<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei1tkyb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei1tkyb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:comment-text" {...props}></Icon>
