<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqv05h9mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqv05h9mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:computer-sharp" {...props}></Icon>
