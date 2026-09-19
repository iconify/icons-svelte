<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikuyx85cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ikuyx85cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:combination-lock" {...props}></Icon>
