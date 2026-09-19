<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hibq6ccco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hibq6ccco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:clover-spiked" {...props}></Icon>
