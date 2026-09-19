<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg_k29_bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yg_k29_bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:eyedropper-halffull" {...props}></Icon>
