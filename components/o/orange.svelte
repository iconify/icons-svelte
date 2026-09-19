<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfmwm-blc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sfmwm-blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:orange" {...props}></Icon>
