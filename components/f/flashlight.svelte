<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr3c7yb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yr3c7yb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flashlight" {...props}></Icon>
