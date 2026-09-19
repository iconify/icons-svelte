<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyxzshb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iyxzshb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ion-cannon-blast" {...props}></Icon>
