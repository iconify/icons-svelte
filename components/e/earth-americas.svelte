<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9xm4ynen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y9xm4ynen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:earth-americas" {...props}></Icon>
