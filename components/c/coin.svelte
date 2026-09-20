<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4go9bboz.css';
import '../../css/y/y1vck7bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="o4go9bboz"/><path class="y1vck7bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:coin" {...props}></Icon>
