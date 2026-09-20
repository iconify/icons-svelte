<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1rs_hvhx.css';
import '../../css/z/zsi22_bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g1rs_hvhx"/><path class="zsi22_bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:blinko" {...props}></Icon>
