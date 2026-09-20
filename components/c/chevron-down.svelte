<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm_k6g8zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm_k6g8zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chevron-down" {...props}></Icon>
