<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly-1yssge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ly-1yssge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pikeman" {...props}></Icon>
