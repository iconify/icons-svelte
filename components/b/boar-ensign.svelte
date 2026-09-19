<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq6_tcb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hq6_tcb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boar-ensign" {...props}></Icon>
