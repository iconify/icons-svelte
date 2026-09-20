<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7-vrkbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i7-vrkbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:jp-lighthouse" {...props}></Icon>
