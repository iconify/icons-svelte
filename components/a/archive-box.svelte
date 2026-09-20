<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acjvezy8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="acjvezy8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:archive-box" {...props}></Icon>
