<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wipq2ibhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wipq2ibhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bulldozer" {...props}></Icon>
