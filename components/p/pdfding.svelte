<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzzcr4b4h.css';
import '../../css/y/ynjyyh6_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="jzzcr4b4h"/><path class="ynjyyh6_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pdfding" {...props}></Icon>
