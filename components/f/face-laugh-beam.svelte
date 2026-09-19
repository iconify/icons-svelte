<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfja0szta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rfja0szta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-laugh-beam" {...props}></Icon>
