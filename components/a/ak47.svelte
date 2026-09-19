<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5c1m7t2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z5c1m7t2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ak47" {...props}></Icon>
