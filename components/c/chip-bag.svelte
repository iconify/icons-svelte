<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh7z4ubgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nh7z4ubgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:chip-bag" {...props}></Icon>
