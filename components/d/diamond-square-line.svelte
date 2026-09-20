<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl4lvpuyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl4lvpuyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diamond-square-line" {...props}></Icon>
