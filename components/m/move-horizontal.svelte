<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yneekqblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yneekqblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:move-horizontal" {...props}></Icon>
