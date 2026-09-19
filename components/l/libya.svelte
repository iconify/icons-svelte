<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqseh9bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqseh9bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:libya" {...props}></Icon>
