<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue-cr-o1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ue-cr-o1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:dashboard" {...props}></Icon>
