<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml9fjm54e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ml9fjm54e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:artichoke" {...props}></Icon>
