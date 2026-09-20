<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pngwd12fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pngwd12fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:paper-plane" {...props}></Icon>
