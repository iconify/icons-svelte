<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piuweebqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="piuweebqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:forward-circle-outline" {...props}></Icon>
