<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scyd3qb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scyd3qb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:gallery-thumbnails-sharp" {...props}></Icon>
