<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb4_wab6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb4_wab6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-bolt" {...props}></Icon>
