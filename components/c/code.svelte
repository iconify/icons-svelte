<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lctqtk5pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="lctqtk5pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:code" {...props}></Icon>
