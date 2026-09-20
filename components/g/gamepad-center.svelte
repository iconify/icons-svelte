<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri5exfbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ri5exfbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-center" {...props}></Icon>
