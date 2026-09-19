<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2nxf_b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="t2nxf_b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:laptop-medical" {...props}></Icon>
