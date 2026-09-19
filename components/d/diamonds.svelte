<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh4wzvbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gh4wzvbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:diamonds" {...props}></Icon>
