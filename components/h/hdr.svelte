<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti-pj-x_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ti-pj-x_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:hdr" {...props}></Icon>
