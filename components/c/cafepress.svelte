<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5nh_xbpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t5nh_xbpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cafepress" {...props}></Icon>
