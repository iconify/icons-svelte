<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzlibj07q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzlibj07q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rocket-circle-filled" {...props}></Icon>
