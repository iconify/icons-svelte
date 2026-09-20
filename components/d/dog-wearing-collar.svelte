<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u12cutb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u12cutb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-wearing-collar" {...props}></Icon>
