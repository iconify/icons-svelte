<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gniy5bk_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gniy5bk_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:logic-gate-not" {...props}></Icon>
