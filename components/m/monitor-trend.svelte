<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_ud2de9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i_ud2de9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:monitor-trend" {...props}></Icon>
