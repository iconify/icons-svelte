<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-bp5d1bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w-bp5d1bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:round-shield" {...props}></Icon>
