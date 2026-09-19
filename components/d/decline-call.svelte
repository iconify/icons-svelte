<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9qaknzwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="m9qaknzwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:decline-call" {...props}></Icon>
