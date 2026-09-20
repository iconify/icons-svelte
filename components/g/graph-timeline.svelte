<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psoz5jj8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psoz5jj8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:graph-timeline" {...props}></Icon>
