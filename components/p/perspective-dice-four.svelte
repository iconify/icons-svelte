<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5jbk3b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s5jbk3b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perspective-dice-four" {...props}></Icon>
