<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8tttibte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="c8tttibte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:calendar-week-filled" {...props}></Icon>
