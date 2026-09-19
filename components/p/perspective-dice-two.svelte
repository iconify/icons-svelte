<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo71e5b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xo71e5b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perspective-dice-two" {...props}></Icon>
