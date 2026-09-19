<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj1uhs6yz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kj1uhs6yz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:barracks" {...props}></Icon>
