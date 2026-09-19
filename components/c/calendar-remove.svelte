<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv3x2zbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="gv3x2zbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:calendar-remove" {...props}></Icon>
