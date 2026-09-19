<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm_wj2bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dm_wj2bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bullhorn" {...props}></Icon>
