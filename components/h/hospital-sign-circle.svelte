<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm-8mhb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="rm-8mhb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hospital-sign-circle" {...props}></Icon>
