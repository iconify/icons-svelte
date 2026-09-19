<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl6warb1x.css';
import '../../css/w/wwtp25bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl6warb1x"/><path class="wwtp25bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:location-x" {...props}></Icon>
