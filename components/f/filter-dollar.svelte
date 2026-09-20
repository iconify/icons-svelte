<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad29uwbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad29uwbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-dollar" {...props}></Icon>
