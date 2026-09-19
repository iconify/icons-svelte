<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/obdrwxfti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="obdrwxfti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:disc-play-2" {...props}></Icon>
