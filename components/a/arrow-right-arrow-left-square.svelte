<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs9dc65rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rs9dc65rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-right-arrow-left-square" {...props}></Icon>
