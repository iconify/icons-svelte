<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm7axpb_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nm7axpb_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:ford" {...props}></Icon>
