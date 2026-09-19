<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x52nqvb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x52nqvb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fertilizer-bag" {...props}></Icon>
