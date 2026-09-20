<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rngp1fbyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rngp1fbyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:horse-head-solid" {...props}></Icon>
