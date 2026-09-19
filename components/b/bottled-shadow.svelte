<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pszgp0b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pszgp0b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bottled-shadow" {...props}></Icon>
