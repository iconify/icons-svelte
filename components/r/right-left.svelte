<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu7ledbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hu7ledbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:right-left" {...props}></Icon>
