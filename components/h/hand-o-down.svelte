<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dufl35bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<g transform="translate(0 1792) scale(1 -1)"><path class="dufl35bfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hand-o-down" {...props}></Icon>
