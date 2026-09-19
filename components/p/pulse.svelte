<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3yw4b3zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n3yw4b3zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pulse" {...props}></Icon>
