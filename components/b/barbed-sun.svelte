<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tncbkw9vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tncbkw9vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:barbed-sun" {...props}></Icon>
