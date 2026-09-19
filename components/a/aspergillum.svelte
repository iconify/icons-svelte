<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw69o2b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iw69o2b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:aspergillum" {...props}></Icon>
