<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqm0ns9os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="gqm0ns9os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:anchor" {...props}></Icon>
