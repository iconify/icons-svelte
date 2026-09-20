<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yno5idtej.css';
import '../../css/u/uve6c28av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yno5idtej"/><path class="uve6c28av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-pie-filled" {...props}></Icon>
