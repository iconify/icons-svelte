<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx3qko77u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nx3qko77u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:linden-leaf" {...props}></Icon>
