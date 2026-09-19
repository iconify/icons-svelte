<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtm3r7b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rtm3r7b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chart-bar-alt-fill" {...props}></Icon>
