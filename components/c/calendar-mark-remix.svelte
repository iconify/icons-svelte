<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf_ncgock.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rf_ncgock"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:calendar-mark-remix" {...props}></Icon>
