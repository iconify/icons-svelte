<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlzazsb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlzazsb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:picture-in-picture-alt" {...props}></Icon>
