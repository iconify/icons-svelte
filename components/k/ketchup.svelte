<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tav7wc75e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tav7wc75e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ketchup" {...props}></Icon>
