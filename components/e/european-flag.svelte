<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms4wiabgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ms4wiabgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:european-flag" {...props}></Icon>
