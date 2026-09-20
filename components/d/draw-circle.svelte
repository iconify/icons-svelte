<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6t9uc-4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q6t9uc-4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:draw-circle" {...props}></Icon>
