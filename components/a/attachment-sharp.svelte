<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vov1yw3_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vov1yw3_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:attachment-sharp" {...props}></Icon>
