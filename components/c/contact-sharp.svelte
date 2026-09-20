<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1_h6wber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1_h6wber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:contact-sharp" {...props}></Icon>
