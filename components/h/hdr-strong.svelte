<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub6p_vdiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="ub6p_vdiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:hdr-strong" {...props}></Icon>
