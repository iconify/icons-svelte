<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckycwgbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ckycwgbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:poll-h" {...props}></Icon>
