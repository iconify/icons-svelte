<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqd3i0b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqd3i0b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:analytics-graph-lines-2-bold" {...props}></Icon>
