<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1cyggo8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="v1cyggo8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grin-tongue-wink" {...props}></Icon>
