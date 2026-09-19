<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_lq4bvop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="p_lq4bvop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:head-side-mask" {...props}></Icon>
