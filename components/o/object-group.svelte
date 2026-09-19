<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2q5z-wrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2q5z-wrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:object-group" {...props}></Icon>
