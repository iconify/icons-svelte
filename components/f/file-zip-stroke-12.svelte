<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf6mrnboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xf6mrnboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-zip-stroke-12" {...props}></Icon>
