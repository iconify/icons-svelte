<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf4g5ckay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="cf4g5ckay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:foot-sign" {...props}></Icon>
