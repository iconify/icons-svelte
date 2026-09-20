<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a13q3r_5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a13q3r_5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hearing-accessibility-symbol-with-t" {...props}></Icon>
