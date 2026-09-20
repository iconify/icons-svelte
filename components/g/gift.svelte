<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-_uj7vqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-_uj7vqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:gift" {...props}></Icon>
