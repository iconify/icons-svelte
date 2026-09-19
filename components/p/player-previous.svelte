<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9-mh3b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y9-mh3b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:player-previous" {...props}></Icon>
