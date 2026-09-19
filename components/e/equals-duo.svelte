<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r87km9-rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="r87km9-rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:equals-duo" {...props}></Icon>
