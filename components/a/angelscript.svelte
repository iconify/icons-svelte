<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixwq2bc2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ixwq2bc2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:angelscript" {...props}></Icon>
