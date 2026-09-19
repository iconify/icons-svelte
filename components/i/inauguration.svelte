<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu74euvyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lu74euvyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:inauguration" {...props}></Icon>
