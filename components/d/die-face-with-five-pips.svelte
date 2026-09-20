<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozs9embjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ozs9embjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:die-face-with-five-pips" {...props}></Icon>
