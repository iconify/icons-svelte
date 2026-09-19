<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk-v9cckq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="pk-v9cckq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bread" {...props}></Icon>
