<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ago6k6csm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ago6k6csm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:biscuit" {...props}></Icon>
