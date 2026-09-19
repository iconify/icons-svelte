<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgk_xe5yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kgk_xe5yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rolling-energy" {...props}></Icon>
