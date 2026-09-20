<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bao4k39lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bao4k39lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:airplane-cog" {...props}></Icon>
