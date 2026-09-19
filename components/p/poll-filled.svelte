<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5xbnj3bp.css';
import '../../css/t/t1563xbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5xbnj3bp"/><rect class="t1563xbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:poll-filled" {...props}></Icon>
