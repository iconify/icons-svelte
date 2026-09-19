<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw_2-2akj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw_2-2akj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-direction-left" {...props}></Icon>
