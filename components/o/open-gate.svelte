<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whhsbdc7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="whhsbdc7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:open-gate" {...props}></Icon>
