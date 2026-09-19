<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xemudqboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="xemudqboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bomb-1" {...props}></Icon>
