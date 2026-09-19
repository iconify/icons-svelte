<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz55uh92z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qz55uh92z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:group-discussion-meetingx3-outline" {...props}></Icon>
