<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a02s0cczt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a02s0cczt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:book-with-arrows-recirculating" {...props}></Icon>
