<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-scc5p3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p-scc5p3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:browser" {...props}></Icon>
