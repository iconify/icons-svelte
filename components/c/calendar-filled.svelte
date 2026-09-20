<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huuz7bb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="huuz7bb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:calendar-filled" {...props}></Icon>
