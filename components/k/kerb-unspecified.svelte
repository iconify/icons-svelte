<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq1wgzb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pq1wgzb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:kerb-unspecified" {...props}></Icon>
