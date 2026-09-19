<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez__yk4iu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ez__yk4iu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:calculator-2" {...props}></Icon>
