<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8_q7kbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h8_q7kbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:male" {...props}></Icon>
