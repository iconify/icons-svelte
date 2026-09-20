<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa4glgq1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="aa4glgq1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:indent-rtl" {...props}></Icon>
