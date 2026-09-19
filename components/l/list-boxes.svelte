<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1qpnvb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q1qpnvb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:list-boxes" {...props}></Icon>
