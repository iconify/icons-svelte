<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwv14-5so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":408};
const content = `<path class="cwv14-5so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:case-play" {...props}></Icon>
