<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot-8tac3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ot-8tac3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:divided-spiral" {...props}></Icon>
