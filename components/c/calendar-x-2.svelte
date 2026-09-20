<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bju59sbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bju59sbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:calendar-x-2" {...props}></Icon>
