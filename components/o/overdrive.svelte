<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffouq9b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffouq9b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:overdrive" {...props}></Icon>
