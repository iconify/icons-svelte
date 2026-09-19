<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhqy3-bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mhqy3-bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mimic-chest" {...props}></Icon>
