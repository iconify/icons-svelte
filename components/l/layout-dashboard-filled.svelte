<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv05c1bvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv05c1bvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-dashboard-filled" {...props}></Icon>
