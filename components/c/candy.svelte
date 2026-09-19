<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of5620y8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="of5620y8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:candy" {...props}></Icon>
