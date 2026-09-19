<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yynj4_2gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yynj4_2gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:lovable" {...props}></Icon>
