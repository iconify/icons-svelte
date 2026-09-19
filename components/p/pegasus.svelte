<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcennbbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xcennbbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pegasus" {...props}></Icon>
