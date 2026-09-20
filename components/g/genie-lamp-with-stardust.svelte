<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr_ri1bdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rr_ri1bdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:genie-lamp-with-stardust" {...props}></Icon>
