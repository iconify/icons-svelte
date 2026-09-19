<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdkb-obmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tdkb-obmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:egg-pod" {...props}></Icon>
