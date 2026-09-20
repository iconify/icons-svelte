<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdhxq_bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdhxq_bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-circle-outline" {...props}></Icon>
