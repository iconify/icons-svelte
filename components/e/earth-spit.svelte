<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9hxqcc5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9hxqcc5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:earth-spit" {...props}></Icon>
