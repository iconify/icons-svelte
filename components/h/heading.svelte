<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsv_vsx-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hsv_vsx-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:heading" {...props}></Icon>
