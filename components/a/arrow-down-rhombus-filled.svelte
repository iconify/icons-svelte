<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1w6ya-bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1w6ya-bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-down-rhombus-filled" {...props}></Icon>
