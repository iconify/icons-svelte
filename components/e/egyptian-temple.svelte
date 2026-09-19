<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubrg13b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ubrg13b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:egyptian-temple" {...props}></Icon>
