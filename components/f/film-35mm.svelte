<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsx39kbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bsx39kbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:film-35mm" {...props}></Icon>
