<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx9izvgqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kx9izvgqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:icons" {...props}></Icon>
