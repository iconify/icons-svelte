<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylobwvhsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1728,"height":1280};
const content = `<g transform="translate(1728 0) scale(-1 1)"><path class="ylobwvhsp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:long-arrow-right" {...props}></Icon>
