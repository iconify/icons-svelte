<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xltittbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xltittbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-viii" {...props}></Icon>
