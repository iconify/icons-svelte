<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbc9occ-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbc9occ-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-plus-outline" {...props}></Icon>
