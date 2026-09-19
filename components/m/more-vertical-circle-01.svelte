<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl_82zymi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl_82zymi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:more-vertical-circle-01" {...props}></Icon>
