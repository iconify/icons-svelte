<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm7dvmcxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="mm7dvmcxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:extinguisher" {...props}></Icon>
