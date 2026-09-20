<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi81hpblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi81hpblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phonelink-erase" {...props}></Icon>
