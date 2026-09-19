<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rujiq5bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="rujiq5bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:magic" {...props}></Icon>
