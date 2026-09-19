<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln91y3bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ln91y3bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mineral-pearls" {...props}></Icon>
