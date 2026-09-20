<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfx2fdc4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gfx2fdc4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peppermint" {...props}></Icon>
