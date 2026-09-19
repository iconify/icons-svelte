<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqjhhacny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<g transform="translate(1536 0) scale(-1 1)"><path class="iqjhhacny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:arrow-circle-o-right" {...props}></Icon>
