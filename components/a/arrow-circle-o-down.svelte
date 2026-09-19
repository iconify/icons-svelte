<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-922rvxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<g transform="translate(0 1536) scale(1 -1)"><path class="b-922rvxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:arrow-circle-o-down" {...props}></Icon>
