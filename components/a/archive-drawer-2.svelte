<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yle6jzvgh.css';
import '../../css/x/xug9tx33p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yle6jzvgh"/><path class="xug9tx33p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:archive-drawer-2" {...props}></Icon>
