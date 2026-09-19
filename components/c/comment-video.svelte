<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whoz7fbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="whoz7fbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:comment-video" {...props}></Icon>
