<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-0wqubyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x-0wqubyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cars-on-barge-on-water" {...props}></Icon>
