<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnf9-xb3q.css';
import '../../css/j/j6xrxv6-w.css';
import '../../css/z/zw-s4mi4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnf9-xb3q"/><path class="j6xrxv6-w"/><path class="zw-s4mi4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calendar-mark-bold-duotone" {...props}></Icon>
