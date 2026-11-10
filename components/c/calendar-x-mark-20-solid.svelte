<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peon_xbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="peon_xbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-x-mark-20-solid" {...props}></Icon>
