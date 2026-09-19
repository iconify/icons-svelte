<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvgu6skht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fvgu6skht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:gluttonous-smile" {...props}></Icon>
