<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaan1_bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oaan1_bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:notebook" {...props}></Icon>
