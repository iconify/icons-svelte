<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygj31lgsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ygj31lgsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:button-triangle-up" {...props}></Icon>
