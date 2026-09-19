<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v23ra87cd.css';
import '../../css/g/g8g7_q-fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v23ra87cd"/><path class="g8g7_q-fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:room" {...props}></Icon>
