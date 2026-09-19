<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bff9_4afs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="bff9_4afs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:downstair" {...props}></Icon>
