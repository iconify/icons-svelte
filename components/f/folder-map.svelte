<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ift36sbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ift36sbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:folder-map" {...props}></Icon>
