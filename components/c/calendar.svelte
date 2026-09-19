<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5tz98iyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="f5tz98iyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:calendar" {...props}></Icon>
