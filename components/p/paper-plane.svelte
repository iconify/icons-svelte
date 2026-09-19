<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffzimobwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffzimobwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:paper-plane" {...props}></Icon>
