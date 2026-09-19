<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6d77db6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c6d77db6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:perspective-dice-five" {...props}></Icon>
