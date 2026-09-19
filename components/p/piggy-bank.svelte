<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp_uagnzf.css';
import '../../css/z/zwr_uxclv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp_uagnzf"/><path class="zwr_uxclv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:piggy-bank" {...props}></Icon>
