<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h37kj2bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h37kj2bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:contact-delete" {...props}></Icon>
