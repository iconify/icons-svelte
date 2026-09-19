<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnfb1u0jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pnfb1u0jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-smile-wink" {...props}></Icon>
