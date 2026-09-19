<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl_3d6bty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":384};
const content = `<path class="xl_3d6bty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:airline-seat-legroom-extra" {...props}></Icon>
