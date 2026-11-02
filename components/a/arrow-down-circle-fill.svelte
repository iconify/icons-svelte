<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgr5oj_9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgr5oj_9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-down-circle-fill" {...props}></Icon>
