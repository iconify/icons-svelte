<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xme-khm4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="xme-khm4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:bullhorn" {...props}></Icon>
