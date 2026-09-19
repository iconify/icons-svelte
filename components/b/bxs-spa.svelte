<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do0n5ibbt.css';
import '../../css/n/nnksa96uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="do0n5ibbt"/><path class="nnksa96uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-spa" {...props}></Icon>
