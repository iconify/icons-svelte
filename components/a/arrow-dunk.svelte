<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svacbdx0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="svacbdx0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:arrow-dunk" {...props}></Icon>
