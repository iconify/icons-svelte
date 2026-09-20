<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq_irubvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq_irubvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:funnel-outline" {...props}></Icon>
