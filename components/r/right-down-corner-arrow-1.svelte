<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gta3qn_yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gta3qn_yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:right-down-corner-arrow-1" {...props}></Icon>
