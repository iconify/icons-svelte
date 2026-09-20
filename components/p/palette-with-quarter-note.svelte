<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyc6aqbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cyc6aqbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:palette-with-quarter-note" {...props}></Icon>
