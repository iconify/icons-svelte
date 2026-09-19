<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzvs8lbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="pzvs8lbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bank" {...props}></Icon>
