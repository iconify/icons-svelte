<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6_n2_bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6_n2_bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:diun-dash-light" {...props}></Icon>
