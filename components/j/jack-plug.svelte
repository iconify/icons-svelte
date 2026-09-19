<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvx9auxoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kvx9auxoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jack-plug" {...props}></Icon>
