<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n58_tkbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n58_tkbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fast-backward-button" {...props}></Icon>
