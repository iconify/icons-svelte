<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu7tyx5et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uu7tyx5et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:dashboard-pen" {...props}></Icon>
