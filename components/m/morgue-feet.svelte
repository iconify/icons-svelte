<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov6u5_g5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ov6u5_g5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:morgue-feet" {...props}></Icon>
