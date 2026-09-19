<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_wm2bcss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q_wm2bcss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gamepad-cross" {...props}></Icon>
