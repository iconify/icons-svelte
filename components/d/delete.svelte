<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpfgoza3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="zpfgoza3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:delete" {...props}></Icon>
