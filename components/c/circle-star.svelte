<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acp87jbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="acp87jbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:circle-star" {...props}></Icon>
