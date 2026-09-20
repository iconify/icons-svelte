<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5flc7b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5flc7b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:aspect-ratio-sharp" {...props}></Icon>
