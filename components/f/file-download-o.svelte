<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjuv5pbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1536};
const content = `<path class="cjuv5pbie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:file-download-o" {...props}></Icon>
