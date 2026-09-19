<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8zny-epf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q8zny-epf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:female-legs" {...props}></Icon>
