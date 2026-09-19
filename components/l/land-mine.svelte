<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec_g-0b5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ec_g-0b5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:land-mine" {...props}></Icon>
