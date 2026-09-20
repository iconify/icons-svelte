<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc4cc4t7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sc4cc4t7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flagstick-with-pennant-on-square" {...props}></Icon>
