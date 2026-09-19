<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f55eazy9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f55eazy9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:old-wagon" {...props}></Icon>
