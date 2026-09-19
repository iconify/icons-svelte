<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5ky9xbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k5ky9xbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:load" {...props}></Icon>
