<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yla7zvbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yla7zvbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abacus" {...props}></Icon>
