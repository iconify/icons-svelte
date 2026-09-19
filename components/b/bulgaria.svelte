<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ou4zimbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ou4zimbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bulgaria" {...props}></Icon>
