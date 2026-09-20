<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huhyvzy8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huhyvzy8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-minus" {...props}></Icon>
