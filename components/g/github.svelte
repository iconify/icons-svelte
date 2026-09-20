<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vop2ck--i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vop2ck--i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:github" {...props}></Icon>
