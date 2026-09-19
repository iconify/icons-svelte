<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfoxw2uzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nfoxw2uzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:first-aid-kit" {...props}></Icon>
