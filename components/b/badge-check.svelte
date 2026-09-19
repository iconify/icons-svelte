<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4z4z2_dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":480};
const content = `<path class="y4z4z2_dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:badge-check" {...props}></Icon>
