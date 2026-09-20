<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udhkbmo8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udhkbmo8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:moon-new" {...props}></Icon>
