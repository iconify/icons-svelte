<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ash7njbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ash7njbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:acid-tube" {...props}></Icon>
