<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef2r0cbam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ef2r0cbam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:newspaper" {...props}></Icon>
