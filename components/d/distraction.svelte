<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlr1xxbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jlr1xxbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:distraction" {...props}></Icon>
