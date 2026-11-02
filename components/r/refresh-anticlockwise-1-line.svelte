<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltr91uweb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltr91uweb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-anticlockwise-1-line" {...props}></Icon>
