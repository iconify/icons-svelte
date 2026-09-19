<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o73412c5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o73412c5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rear-aura" {...props}></Icon>
