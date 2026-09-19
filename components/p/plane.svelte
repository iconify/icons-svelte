<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_o2s1b2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="g_o2s1b2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:plane" {...props}></Icon>
