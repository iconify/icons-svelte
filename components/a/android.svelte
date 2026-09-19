<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beh7sz67x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="beh7sz67x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:android" {...props}></Icon>
