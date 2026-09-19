<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o75hfuw-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o75hfuw-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:campfire" {...props}></Icon>
