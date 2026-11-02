<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frlgpc51z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frlgpc51z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:leaf-fill" {...props}></Icon>
