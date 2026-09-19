<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1f07vhbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m1f07vhbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:juggling-clubs" {...props}></Icon>
