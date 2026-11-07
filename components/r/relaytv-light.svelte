<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unodwm65o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="unodwm65o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:relaytv-light" {...props}></Icon>
