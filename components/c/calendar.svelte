<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su1uxpbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="su1uxpbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:calendar" {...props}></Icon>
