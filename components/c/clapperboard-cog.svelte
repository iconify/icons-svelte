<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5mm9kbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k5mm9kbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clapperboard-cog" {...props}></Icon>
