<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onw2bx3kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="onw2bx3kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:battery-50" {...props}></Icon>
