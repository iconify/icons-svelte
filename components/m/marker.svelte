<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epcjm8b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epcjm8b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:marker" {...props}></Icon>
