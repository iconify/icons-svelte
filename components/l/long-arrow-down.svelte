<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st6matk8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1728};
const content = `<g transform="translate(0 1728) scale(1 -1)"><path class="st6matk8b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:long-arrow-down" {...props}></Icon>
