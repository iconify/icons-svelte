<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhovvmb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dhovvmb6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:logic-gate-xor" {...props}></Icon>
