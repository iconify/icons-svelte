<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un0pq6cid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un0pq6cid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:rotate-rectangle" {...props}></Icon>
