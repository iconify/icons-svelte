<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7i-_hv-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p7i-_hv-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:folder-open" {...props}></Icon>
