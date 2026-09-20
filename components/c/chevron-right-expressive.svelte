<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdt2dg_fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdt2dg_fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:chevron-right-expressive" {...props}></Icon>
