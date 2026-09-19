<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-nq93blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="y-nq93blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:barcode" {...props}></Icon>
