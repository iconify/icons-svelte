<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-qp-ebuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m-qp-ebuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:great-war-tank" {...props}></Icon>
