<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe5optbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fe5optbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pilcrow" {...props}></Icon>
