<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wugs8pltu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wugs8pltu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hetzner-dark" {...props}></Icon>
