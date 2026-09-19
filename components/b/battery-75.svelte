<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmbl014od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmbl014od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:battery-75" {...props}></Icon>
