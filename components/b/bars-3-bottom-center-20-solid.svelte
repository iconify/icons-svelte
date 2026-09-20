<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/varzj22qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="varzj22qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bars-3-bottom-center-20-solid" {...props}></Icon>
