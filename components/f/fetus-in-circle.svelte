<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5pt64b6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i5pt64b6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fetus-in-circle" {...props}></Icon>
