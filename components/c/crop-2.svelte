<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r__jeok_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="r__jeok_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:crop-2" {...props}></Icon>
