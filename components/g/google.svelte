<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/viruazbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":424,"height":432};
const content = `<path class="viruazbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:google" {...props}></Icon>
