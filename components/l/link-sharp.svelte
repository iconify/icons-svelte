<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk5j9gbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk5j9gbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:link-sharp" {...props}></Icon>
