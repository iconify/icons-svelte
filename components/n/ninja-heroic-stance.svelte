<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9-dgebld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j9-dgebld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ninja-heroic-stance" {...props}></Icon>
