<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa8kjxzjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="sa8kjxzjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:arrow-thin-left" {...props}></Icon>
