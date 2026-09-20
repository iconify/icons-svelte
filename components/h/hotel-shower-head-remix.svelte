<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt_ce3hdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rt_ce3hdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hotel-shower-head-remix" {...props}></Icon>
