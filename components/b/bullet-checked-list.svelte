<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxq95pbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pxq95pbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bullet-checked-list" {...props}></Icon>
