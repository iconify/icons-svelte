<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu9fh_blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu9fh_blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:ampersand-sharp" {...props}></Icon>
