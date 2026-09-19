<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpntzicry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hpntzicry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cursor-2" {...props}></Icon>
