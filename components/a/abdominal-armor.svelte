<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj8m8pbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qj8m8pbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abdominal-armor" {...props}></Icon>
