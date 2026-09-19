<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhl-0tduv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="bhl-0tduv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:botl-2" {...props}></Icon>
