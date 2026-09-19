<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f324_hb1n.css';
import '../../css/e/edm1wthdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":44,"height":44};
const content = `<rect class="f324_hb1n"/><path class="edm1wthdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:checkbox" {...props}></Icon>
