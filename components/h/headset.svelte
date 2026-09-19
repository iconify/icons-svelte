<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm6pyibmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fm6pyibmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:headset" {...props}></Icon>
