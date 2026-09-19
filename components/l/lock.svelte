<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0tpe6_5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="w0tpe6_5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:lock" {...props}></Icon>
