<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5u9rbcmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n5u9rbcmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magic-palm" {...props}></Icon>
