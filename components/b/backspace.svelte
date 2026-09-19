<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2t8b4_yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q2t8b4_yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:backspace" {...props}></Icon>
