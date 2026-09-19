<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1v1gjlxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":480};
const content = `<path class="z1v1gjlxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-speaker" {...props}></Icon>
