<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw5g0xbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yw5g0xbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrows-alt" {...props}></Icon>
