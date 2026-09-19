<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cto2kz5ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cto2kz5ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dig-dug" {...props}></Icon>
