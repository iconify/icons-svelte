<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wblvtj5oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wblvtj5oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:folder-maps" {...props}></Icon>
