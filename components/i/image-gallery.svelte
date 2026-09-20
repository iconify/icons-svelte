<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsfsse0hi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsfsse0hi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:image-gallery" {...props}></Icon>
