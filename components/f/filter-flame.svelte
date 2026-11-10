<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1ehnebjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i1ehnebjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-flame" {...props}></Icon>
