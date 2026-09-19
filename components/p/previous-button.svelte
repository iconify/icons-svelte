<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_ww-5bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f_ww-5bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:previous-button" {...props}></Icon>
