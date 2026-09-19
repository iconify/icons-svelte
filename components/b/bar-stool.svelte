<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn-h4zb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xn-h4zb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bar-stool" {...props}></Icon>
