<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh8ym9dvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jh8ym9dvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:draw-circle-arc" {...props}></Icon>
