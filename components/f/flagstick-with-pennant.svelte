<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peplw6b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="peplw6b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flagstick-with-pennant" {...props}></Icon>
