<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc1by1b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oc1by1b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:printer" {...props}></Icon>
