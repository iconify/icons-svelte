<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjtsj09io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cjtsj09io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:radio" {...props}></Icon>
