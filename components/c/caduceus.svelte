<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkncd8bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mkncd8bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:caduceus" {...props}></Icon>
