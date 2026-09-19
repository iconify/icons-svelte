<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1j79ab8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n1j79ab8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:eclipse-saw" {...props}></Icon>
