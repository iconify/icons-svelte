<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxh4johuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="vxh4johuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:poker-3" {...props}></Icon>
