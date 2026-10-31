<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6_r6x8xh.css';
import '../../css/h/hkoftybrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="z6_r6x8xh"/><path class="hkoftybrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:nordic-council" {...props}></Icon>
