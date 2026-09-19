<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w30-vrati.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w30-vrati"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:leaf-swirl" {...props}></Icon>
