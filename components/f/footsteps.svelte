<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tje43xbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tje43xbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:footsteps" {...props}></Icon>
