<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb8b2yvin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yb8b2yvin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:cowled" {...props}></Icon>
