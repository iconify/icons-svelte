<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj1ucjb-u.css';
import '../../css/i/ixx-con_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tj1ucjb-u"/><path class="ixx-con_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:network-public" {...props}></Icon>
