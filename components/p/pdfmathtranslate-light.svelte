<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fllq90bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fllq90bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pdfmathtranslate-light" {...props}></Icon>
