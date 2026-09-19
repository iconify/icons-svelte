<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnz76ruct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tnz76ruct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gravitation" {...props}></Icon>
