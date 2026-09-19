<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zj5vjvkzr.css';
import '../../css/b/b12gxvr_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zj5vjvkzr"/><circle class="b12gxvr_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-yin-yang" {...props}></Icon>
