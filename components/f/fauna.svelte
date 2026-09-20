<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkvzy8bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkvzy8bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fauna" {...props}></Icon>
