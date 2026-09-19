<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnj8a2e8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tnj8a2e8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fog-light" {...props}></Icon>
