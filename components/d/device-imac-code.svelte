<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muzy8absx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muzy8absx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-code" {...props}></Icon>
