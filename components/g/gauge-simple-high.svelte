<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxvq7acur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wxvq7acur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:gauge-simple-high" {...props}></Icon>
