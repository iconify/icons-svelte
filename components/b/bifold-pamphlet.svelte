<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbaozxt1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rbaozxt1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bifold-pamphlet" {...props}></Icon>
