<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6j-pwior.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t6j-pwior"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:palette" {...props}></Icon>
