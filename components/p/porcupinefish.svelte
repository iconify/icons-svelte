<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgvq16dvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xgvq16dvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:porcupinefish" {...props}></Icon>
