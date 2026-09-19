<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_ara8lji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i_ara8lji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:gg-circle" {...props}></Icon>
