<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gszf4yboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gszf4yboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:raspberry-pi-dark" {...props}></Icon>
