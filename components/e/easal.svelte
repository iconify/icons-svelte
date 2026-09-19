<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjqj9n19a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cjqj9n19a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:easal" {...props}></Icon>
