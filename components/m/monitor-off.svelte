<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1rdnlb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1rdnlb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:monitor-off" {...props}></Icon>
