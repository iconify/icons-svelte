<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e49kknb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e49kknb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:round-rock" {...props}></Icon>
