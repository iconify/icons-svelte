<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfp1htbpz.css';
import '../../css/p/p6s0jubwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfp1htbpz"/><path class="p6s0jubwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:background" {...props}></Icon>
