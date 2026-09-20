<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zovczcbsn.css';
import '../../css/g/g_ku85bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zovczcbsn"/><path class="g_ku85bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:calendar-days" {...props}></Icon>
