<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz9iv6bwq.css';
import '../../css/p/pq0jslbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz9iv6bwq"/><path class="pq0jslbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-right-arrow" {...props}></Icon>
