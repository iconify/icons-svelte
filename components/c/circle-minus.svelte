<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcwwrwb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rcwwrwb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-minus" {...props}></Icon>
