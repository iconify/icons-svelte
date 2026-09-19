<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddiz8c_3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ddiz8c_3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:paper-plane" {...props}></Icon>
