<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oftdd1b0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oftdd1b0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:black-bridge" {...props}></Icon>
