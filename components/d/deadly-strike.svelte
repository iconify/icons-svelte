<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj_2_qbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bj_2_qbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:deadly-strike" {...props}></Icon>
