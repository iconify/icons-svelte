<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg5f894wb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yg5f894wb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:plane-take-off" {...props}></Icon>
