<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soy8-7enc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="soy8-7enc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:coffee-cup" {...props}></Icon>
