<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_kjscwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v3_kjscwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:power-off" {...props}></Icon>
