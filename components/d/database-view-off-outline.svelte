<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl63nfdhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl63nfdhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-view-off-outline" {...props}></Icon>
