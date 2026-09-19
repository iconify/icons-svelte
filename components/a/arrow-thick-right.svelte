<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh2o-wywp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="wh2o-wywp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-thick-right" {...props}></Icon>
