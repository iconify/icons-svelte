<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea9az7bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ea9az7bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:high-five" {...props}></Icon>
