<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu9lgye8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xu9lgye8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pin-pad-with-euro" {...props}></Icon>
