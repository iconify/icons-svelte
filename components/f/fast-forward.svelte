<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u65hmsmhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<g transform="translate(1792 0) scale(-1 1)"><path class="u65hmsmhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:fast-forward" {...props}></Icon>
