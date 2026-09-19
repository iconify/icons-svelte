<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrjc3vb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mrjc3vb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lightning-arc" {...props}></Icon>
