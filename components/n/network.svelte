<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz_xepb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="lz_xepb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:network" {...props}></Icon>
