<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yiz930s_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yiz930s_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-wifi" {...props}></Icon>
