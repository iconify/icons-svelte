<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi9v3xbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oi9v3xbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:monument-valley" {...props}></Icon>
