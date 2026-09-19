<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3uk9lq3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y3uk9lq3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:fan" {...props}></Icon>
