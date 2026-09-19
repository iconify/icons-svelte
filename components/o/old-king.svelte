<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8o-9r21e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w8o-9r21e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:old-king" {...props}></Icon>
