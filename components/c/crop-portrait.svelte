<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtud8ramv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="mtud8ramv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:crop-portrait" {...props}></Icon>
