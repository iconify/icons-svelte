<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohx_6lg8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ohx_6lg8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:forest-entrance" {...props}></Icon>
