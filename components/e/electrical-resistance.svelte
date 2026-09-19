<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyx608bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kyx608bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:electrical-resistance" {...props}></Icon>
