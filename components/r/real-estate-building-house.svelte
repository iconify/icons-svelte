<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi6pzub_r.css';
import '../../css/s/sqglgeskz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oi6pzub_r"/><path class="sqglgeskz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:real-estate-building-house" {...props}></Icon>
