<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvxgn1bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvxgn1bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-right-bold-outline" {...props}></Icon>
