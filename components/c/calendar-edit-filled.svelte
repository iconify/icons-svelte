<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv1b35xpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rv1b35xpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-edit-filled" {...props}></Icon>
