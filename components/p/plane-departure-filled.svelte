<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1s5h0bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1s5h0bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:plane-departure-filled" {...props}></Icon>
