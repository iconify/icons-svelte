<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1lj5vbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a1lj5vbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:face-grimace" {...props}></Icon>
