<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0v512beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t0v512beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dagger-rose" {...props}></Icon>
