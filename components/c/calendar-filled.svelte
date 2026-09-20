<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7_go48_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="v7_go48_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:calendar-filled" {...props}></Icon>
