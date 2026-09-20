<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozxky6mjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozxky6mjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:picture-in-picture-sharp" {...props}></Icon>
