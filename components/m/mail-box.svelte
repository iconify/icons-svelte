<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwwp_sbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="hwwp_sbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:mail-box" {...props}></Icon>
