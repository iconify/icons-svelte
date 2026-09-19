<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbqzj5bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<g transform="translate(1536 0) scale(-1 1)"><path class="wbqzj5bhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:chevron-circle-right" {...props}></Icon>
