<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzzb1zy8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nzzb1zy8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:junie" {...props}></Icon>
