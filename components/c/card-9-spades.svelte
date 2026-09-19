<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jope4zbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jope4zbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:card-9-spades" {...props}></Icon>
