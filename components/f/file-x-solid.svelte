<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgshw4bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgshw4bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:file-x-solid" {...props}></Icon>
