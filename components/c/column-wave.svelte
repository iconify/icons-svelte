<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti7ff3-an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ti7ff3-an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:column-wave" {...props}></Icon>
