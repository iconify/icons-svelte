<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj3s65blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nj3s65blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:circle-sparks" {...props}></Icon>
