<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufi2aab_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ufi2aab_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:encrypted-channel" {...props}></Icon>
