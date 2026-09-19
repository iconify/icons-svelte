<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghg-xobfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ghg-xobfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:marrow-drain" {...props}></Icon>
