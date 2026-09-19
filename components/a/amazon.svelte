<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orbmf1k0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="orbmf1k0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:amazon" {...props}></Icon>
