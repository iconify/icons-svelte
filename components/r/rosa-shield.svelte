<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx3c_8b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rx3c_8b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rosa-shield" {...props}></Icon>
