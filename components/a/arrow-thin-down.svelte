<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drguwkmyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="drguwkmyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-thin-down" {...props}></Icon>
