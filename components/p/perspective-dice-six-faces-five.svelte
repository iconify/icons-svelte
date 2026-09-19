<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcjo14bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gcjo14bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perspective-dice-six-faces-five" {...props}></Icon>
