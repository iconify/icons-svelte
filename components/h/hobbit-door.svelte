<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-d_g7knk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i-d_g7knk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:hobbit-door" {...props}></Icon>
