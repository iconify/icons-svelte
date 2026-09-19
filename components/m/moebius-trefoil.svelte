<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru2o9bykq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ru2o9bykq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:moebius-trefoil" {...props}></Icon>
