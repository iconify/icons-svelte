<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgwi1hb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dgwi1hb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:media-interactive" {...props}></Icon>
