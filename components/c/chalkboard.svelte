<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5z51jagi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="q5z51jagi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chalkboard" {...props}></Icon>
