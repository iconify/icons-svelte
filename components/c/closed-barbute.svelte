<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx0yfxh_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tx0yfxh_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:closed-barbute" {...props}></Icon>
