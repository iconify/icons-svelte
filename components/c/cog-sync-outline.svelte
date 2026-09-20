<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kra9o8bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kra9o8bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cog-sync-outline" {...props}></Icon>
