<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy9yn_biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy9yn_biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:menu-fold-3-line-2" {...props}></Icon>
