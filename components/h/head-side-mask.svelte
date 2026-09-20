<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pil_nmbqz.css';
import '../../css/y/ydj8k-bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pil_nmbqz"/><path class="ydj8k-bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:head-side-mask" {...props}></Icon>
