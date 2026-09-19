<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3bqu011e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g3bqu011e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hatchet" {...props}></Icon>
