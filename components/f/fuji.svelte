<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlz4sml2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tlz4sml2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fuji" {...props}></Icon>
