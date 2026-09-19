<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mem9ylb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mem9ylb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hand-saw" {...props}></Icon>
