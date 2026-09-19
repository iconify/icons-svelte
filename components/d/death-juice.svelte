<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db2na1wqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="db2na1wqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:death-juice" {...props}></Icon>
