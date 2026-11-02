<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es5tsw1hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es5tsw1hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-nigeria-line" {...props}></Icon>
