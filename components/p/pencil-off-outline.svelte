<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldat04b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldat04b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pencil-off-outline" {...props}></Icon>
