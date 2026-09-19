<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv4h6zt4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fv4h6zt4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:rain-showers-day" {...props}></Icon>
