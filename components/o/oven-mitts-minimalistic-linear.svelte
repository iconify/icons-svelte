<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwizfhbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwizfhbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:oven-mitts-minimalistic-linear" {...props}></Icon>
