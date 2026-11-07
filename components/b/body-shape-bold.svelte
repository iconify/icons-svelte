<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf4ca1btm.css';
import '../../css/x/xa-1wqb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf4ca1btm"/><path class="xa-1wqb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:body-shape-bold" {...props}></Icon>
