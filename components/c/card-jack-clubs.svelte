<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ups-hk70t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ups-hk70t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-jack-clubs" {...props}></Icon>
