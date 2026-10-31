<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njjcnycjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njjcnycjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cloud-sync-corner-fill-round" {...props}></Icon>
