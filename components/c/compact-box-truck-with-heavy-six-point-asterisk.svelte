<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0lclmplr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r0lclmplr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:compact-box-truck-with-heavy-six-point-asterisk" {...props}></Icon>
