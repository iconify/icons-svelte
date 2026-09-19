<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn38qzb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<g transform="translate(1792 0) scale(-1 1)"><path class="mn38qzb0f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hand-o-right" {...props}></Icon>
