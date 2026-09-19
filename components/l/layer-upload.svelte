<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnfpavb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="bnfpavb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-upload" {...props}></Icon>
