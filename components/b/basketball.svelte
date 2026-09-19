<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5mbbod_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z5mbbod_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:basketball" {...props}></Icon>
